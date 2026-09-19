<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en51l1bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="en51l1bxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:inverted-dice-6" {...props}></Icon>
