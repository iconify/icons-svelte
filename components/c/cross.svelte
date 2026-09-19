<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap8rfcbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ap8rfcbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:cross" {...props}></Icon>
