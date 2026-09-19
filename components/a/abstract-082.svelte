<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a85az3b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a85az3b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-082" {...props}></Icon>
