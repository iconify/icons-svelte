<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfp4zrbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfp4zrbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-3-box-multiple-outline" {...props}></Icon>
