<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjezifbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjezifbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:mobile-landscape" {...props}></Icon>
