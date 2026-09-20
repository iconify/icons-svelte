<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv4wv-b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv4wv-b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:500px" {...props}></Icon>
