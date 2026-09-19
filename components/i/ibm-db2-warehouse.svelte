<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxnh_641e.css';
import '../../css/t/tiggjjbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hxnh_641e"/><path class="tiggjjbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-db2-warehouse" {...props}></Icon>
