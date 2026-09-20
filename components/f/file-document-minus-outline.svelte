<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxbszvbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxbszvbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-minus-outline" {...props}></Icon>
