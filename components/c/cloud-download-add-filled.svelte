<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig3ggqbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ig3ggqbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-download-add-filled" {...props}></Icon>
