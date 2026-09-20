<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlqqg-bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jlqqg-bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:map-alt-2" {...props}></Icon>
