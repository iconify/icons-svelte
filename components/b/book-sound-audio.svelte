<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbpj61t4x.css';
import '../../css/m/m68w6s2bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbpj61t4x"/><path class="m68w6s2bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:book-sound-audio" {...props}></Icon>
