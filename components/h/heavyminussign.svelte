<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rywc8nbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rywc8nbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heavyminussign" {...props}></Icon>
