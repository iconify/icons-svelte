<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/macoowb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="macoowb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-six-faces-six" {...props}></Icon>
