<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lor2j1w8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lor2j1w8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:j-brick" {...props}></Icon>
