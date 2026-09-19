<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2gf7pbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2gf7pbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-comet" {...props}></Icon>
