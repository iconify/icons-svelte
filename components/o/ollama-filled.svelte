<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unmtxeb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="unmtxeb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:ollama-filled" {...props}></Icon>
