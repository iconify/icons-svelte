<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpk0dxbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpk0dxbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bowl-of-rice" {...props}></Icon>
