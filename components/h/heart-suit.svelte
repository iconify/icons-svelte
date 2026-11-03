<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uroqbab3z.css';
import '../../css/g/gtjqggbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="uroqbab3z"/><path class="gtjqggbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:heart-suit" {...props}></Icon>
