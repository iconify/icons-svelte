<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqtdcnb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="bqtdcnb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-indent-increase" {...props}></Icon>
