<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jri0kqbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jri0kqbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pull" {...props}></Icon>
