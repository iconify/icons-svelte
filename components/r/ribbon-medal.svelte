<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se29b46-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="se29b46-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ribbon-medal" {...props}></Icon>
