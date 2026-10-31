<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo-3fcnkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo-3fcnkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fingerprint-fill-round" {...props}></Icon>
