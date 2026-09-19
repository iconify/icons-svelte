<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r00p3nbjo.css';
import '../../css/r/r0cgx2bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r00p3nbjo"/><path class="r0cgx2bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:robot" {...props}></Icon>
