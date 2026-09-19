<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrb463bje.css';
import '../../css/a/a23i8nphm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jrb463bje"/><path class="a23i8nphm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:nonpotablewatersymbol" {...props}></Icon>
