<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6i2682uu.css';
import '../../css/x/xai0083ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t6i2682uu"/><path class="xai0083ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-board-game-dice" {...props}></Icon>
