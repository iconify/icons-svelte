<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rciznhb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rciznhb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackspadesuit" {...props}></Icon>
