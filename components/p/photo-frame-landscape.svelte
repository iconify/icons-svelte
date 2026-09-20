<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shhnvhbjh.css';
import '../../css/d/duhqzbmzv.css';
import '../../css/w/wsw23sbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shhnvhbjh"/><path class="duhqzbmzv"/><path class="wsw23sbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:photo-frame-landscape" {...props}></Icon>
