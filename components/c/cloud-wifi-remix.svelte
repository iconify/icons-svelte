<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym4bu1bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ym4bu1bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-wifi-remix" {...props}></Icon>
