<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj5amvszy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5amvszy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-left-2-line" {...props}></Icon>
