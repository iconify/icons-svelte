<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzh3qpetg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzh3qpetg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bleeding-eye" {...props}></Icon>
