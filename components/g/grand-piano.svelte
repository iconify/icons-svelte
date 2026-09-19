<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc5nh5bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vc5nh5bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:grand-piano" {...props}></Icon>
