<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6ba4gbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a6ba4gbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-six-faces-four" {...props}></Icon>
