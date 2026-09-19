<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-frsbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq-frsbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-detail-filled" {...props}></Icon>
