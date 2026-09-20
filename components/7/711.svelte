<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwifwsllj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vwifwsllj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:711" {...props}></Icon>
