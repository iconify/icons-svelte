<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tipl4ab7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tipl4ab7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fishing" {...props}></Icon>
