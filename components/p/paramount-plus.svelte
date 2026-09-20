<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn_k6cbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qn_k6cbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paramount-plus" {...props}></Icon>
