<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-mv2ybyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="t-mv2ybyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:facebook" {...props}></Icon>
