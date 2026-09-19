<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfn9nbjqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jfn9nbjqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:harpoon-trident" {...props}></Icon>
