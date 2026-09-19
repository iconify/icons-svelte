<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltdl5wbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ltdl5wbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:playlist-add" {...props}></Icon>
