<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceheq--eq.css';
import '../../css/o/oed997bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ceheq--eq"/><path class="oed997bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:camera-off-filled" {...props}></Icon>
