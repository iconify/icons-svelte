<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utw18ybor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utw18ybor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:json" {...props}></Icon>
