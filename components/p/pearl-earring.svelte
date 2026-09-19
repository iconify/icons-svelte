<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfphd9she.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cfphd9she"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pearl-earring" {...props}></Icon>
