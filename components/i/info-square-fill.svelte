<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtkz3db2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jtkz3db2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:info-square-fill" {...props}></Icon>
