<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4sh_ybhk.css';
import '../../css/z/zna4sbwyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u4sh_ybhk"/><path clip-rule="evenodd" class="zna4sbwyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:camera-solid" {...props}></Icon>
