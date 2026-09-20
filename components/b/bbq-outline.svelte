<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeilkf1ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jeilkf1ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bbq-outline" {...props}></Icon>
