<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjlhq0b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjlhq0b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bloody-sword" {...props}></Icon>
