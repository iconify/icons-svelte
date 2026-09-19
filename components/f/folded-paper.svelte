<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpwu43r9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wpwu43r9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:folded-paper" {...props}></Icon>
