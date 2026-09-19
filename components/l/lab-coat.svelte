<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzw5ddcwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fzw5ddcwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lab-coat" {...props}></Icon>
