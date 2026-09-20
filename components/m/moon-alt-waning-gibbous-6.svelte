<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlbnqc19y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="jlbnqc19y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waning-gibbous-6" {...props}></Icon>
