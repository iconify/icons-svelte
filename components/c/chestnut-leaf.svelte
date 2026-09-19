<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kepe8c3qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kepe8c3qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chestnut-leaf" {...props}></Icon>
