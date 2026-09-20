<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h87n8dxpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h87n8dxpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:certificate" {...props}></Icon>
