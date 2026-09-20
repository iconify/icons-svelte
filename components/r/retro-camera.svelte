<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bji8i1b_f.css';
import '../../css/z/z-imr2beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bji8i1b_f"/><path class="z-imr2beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:retro-camera" {...props}></Icon>
