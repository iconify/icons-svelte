<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/infxvtblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="infxvtblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-valign-top" {...props}></Icon>
