<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7b2ypsge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7b2ypsge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:on-target" {...props}></Icon>
