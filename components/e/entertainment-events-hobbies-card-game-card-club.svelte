<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5_03acjz.css';
import '../../css/a/af92m0fzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d5_03acjz"/><path class="af92m0fzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-card-game-card-club" {...props}></Icon>
