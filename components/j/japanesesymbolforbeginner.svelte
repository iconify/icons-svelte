<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odn0cubmr.css';
import '../../css/k/kbgn2obeo.css';
import '../../css/f/fnb9a-75o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odn0cubmr"/><path class="kbgn2obeo"/><path class="fnb9a-75o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:japanesesymbolforbeginner" {...props}></Icon>
