<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxo54sbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zxo54sbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-z-open-editor" {...props}></Icon>
