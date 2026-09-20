<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfahfob6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tfahfob6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:copy-one-outline" {...props}></Icon>
