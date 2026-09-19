<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di2srog2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="di2srog2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mail-shirt" {...props}></Icon>
