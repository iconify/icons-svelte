<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po-vxz7kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="po-vxz7kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:browser-tab-screenshot" {...props}></Icon>
