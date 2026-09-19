<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8w2yjbbk.css';
import '../../css/c/citsypb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8w2yjbbk"/><path class="citsypb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-arrow" {...props}></Icon>
