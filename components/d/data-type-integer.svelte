<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf77ywbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tf77ywbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:data-type-integer" {...props}></Icon>
