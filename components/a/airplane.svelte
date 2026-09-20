<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqp4kkbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqp4kkbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:airplane" {...props}></Icon>
