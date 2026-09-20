<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rga9k2rpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rga9k2rpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ordered-list" {...props}></Icon>
