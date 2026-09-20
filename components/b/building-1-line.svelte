<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzjxjac2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzjxjac2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-1-line" {...props}></Icon>
