<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf8-382-y.css';
import '../../css/c/c51exofjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hf8-382-y"/><path class="c51exofjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bread" {...props}></Icon>
