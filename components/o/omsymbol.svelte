<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuoip9b-q.css';
import '../../css/i/i2wte8b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xuoip9b-q"/><path class="i2wte8b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:omsymbol" {...props}></Icon>
