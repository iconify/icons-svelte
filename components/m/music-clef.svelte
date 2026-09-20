<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc5uqjbvk.css';
import '../../css/k/kde8vp2lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc5uqjbvk"/><path class="kde8vp2lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:music-clef" {...props}></Icon>
