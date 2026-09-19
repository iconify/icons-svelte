<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ash3_cbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ash3_cbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-tree" {...props}></Icon>
