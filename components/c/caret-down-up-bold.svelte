<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uas7zerge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uas7zerge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:caret-down-up-bold" {...props}></Icon>
