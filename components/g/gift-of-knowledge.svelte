<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/des5-xb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="des5-xb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gift-of-knowledge" {...props}></Icon>
