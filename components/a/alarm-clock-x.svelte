<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgf237vtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgf237vtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:alarm-clock-x" {...props}></Icon>
