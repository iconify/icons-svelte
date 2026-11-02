<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc7c0z81x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc7c0z81x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:appstore-line" {...props}></Icon>
