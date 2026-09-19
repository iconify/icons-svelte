<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukwl3p9vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ukwl3p9vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:book-aura" {...props}></Icon>
