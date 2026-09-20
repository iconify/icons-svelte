<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znnwz6jyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znnwz6jyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-transfer-line" {...props}></Icon>
