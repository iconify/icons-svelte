<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op-6zfyqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op-6zfyqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-notch" {...props}></Icon>
