<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aefv87_qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aefv87_qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:embryo" {...props}></Icon>
