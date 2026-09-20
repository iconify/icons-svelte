<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmar9isaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qmar9isaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:consume-outline" {...props}></Icon>
