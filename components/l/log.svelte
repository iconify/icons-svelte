<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9_d8wlzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9_d8wlzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:log" {...props}></Icon>
