<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr1oq5bin.css';
import '../../css/u/uybrlibii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr1oq5bin"/><path class="uybrlibii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-layer-minus" {...props}></Icon>
