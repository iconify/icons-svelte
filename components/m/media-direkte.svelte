<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5jfs-i_r.css';
import '../../css/f/f9qwu4cot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path clip-rule="evenodd" class="n5jfs-i_r"/><path class="f9qwu4cot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-direkte" {...props}></Icon>
