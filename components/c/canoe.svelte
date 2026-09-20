<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe5jq2kzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="pe5jq2kzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:canoe" {...props}></Icon>
