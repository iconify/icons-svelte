<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfb26sb-e.css';
import '../../css/d/d1x_6zbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="jfb26sb-e"/><path class="d1x_6zbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:austria" {...props}></Icon>
