<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3q08y8ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n3q08y8ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dice-six-faces-four" {...props}></Icon>
