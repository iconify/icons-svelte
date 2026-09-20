<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_05kwblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g_05kwblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anki-dark" {...props}></Icon>
