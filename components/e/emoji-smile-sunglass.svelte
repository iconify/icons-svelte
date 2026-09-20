<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux_-a_76x.css';
import '../../css/h/hdul03-0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux_-a_76x"/><path clip-rule="evenodd" class="hdul03-0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:emoji-smile-sunglass" {...props}></Icon>
