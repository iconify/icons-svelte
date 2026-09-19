<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4dlokacc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e4dlokacc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:code" {...props}></Icon>
