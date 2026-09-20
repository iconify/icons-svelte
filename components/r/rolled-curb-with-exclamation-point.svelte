<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htrmdw6ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="htrmdw6ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rolled-curb-with-exclamation-point" {...props}></Icon>
