<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecnfk-mhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ecnfk-mhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-cloudy-gusts" {...props}></Icon>
