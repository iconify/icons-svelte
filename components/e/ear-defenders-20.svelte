<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syjj109cb.css';
import '../../css/y/yk0otz46s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="syjj109cb"/><path class="yk0otz46s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ear-defenders-20" {...props}></Icon>
