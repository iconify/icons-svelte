<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqrj_zbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qqrj_zbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:kansas" {...props}></Icon>
