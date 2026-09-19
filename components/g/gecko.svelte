<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j350y3b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j350y3b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gecko" {...props}></Icon>
