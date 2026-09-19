<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e78vbih2x.css';
import '../../css/w/wqbkv8u2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e78vbih2x"/><path class="wqbkv8u2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:plus-circle" {...props}></Icon>
