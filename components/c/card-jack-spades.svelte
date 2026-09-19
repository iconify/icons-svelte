<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9dgh665f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x9dgh665f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-jack-spades" {...props}></Icon>
