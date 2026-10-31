<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2w6t3b0i.css';
import '../../css/f/fgh2fcbnj.css';
import '../../css/l/lzc4vcbfk.css';
import '../../css/p/p6h5u-bah.css';
import '../../css/p/pptz10bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="l2w6t3b0i"/><path class="fgh2fcbnj"/><path class="lzc4vcbfk"/><path class="p6h5u-bah"/><path class="pptz10bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:azerbaijan" {...props}></Icon>
