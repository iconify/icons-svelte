<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skpt2nkzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="skpt2nkzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:champions" {...props}></Icon>
