<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1x_6zbkv.css';
import '../../css/f/f6faiabrk.css';
import '../../css/g/gqqnam_xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="f6faiabrk"/><path class="gqqnam_xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:luxembourg" {...props}></Icon>
