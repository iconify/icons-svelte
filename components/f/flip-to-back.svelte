<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvdiahk1x.css';
import '../../css/y/yphrhqbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvdiahk1x"/><path class="yphrhqbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:flip-to-back" {...props}></Icon>
