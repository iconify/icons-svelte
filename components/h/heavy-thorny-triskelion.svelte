<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x77uurkxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x77uurkxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heavy-thorny-triskelion" {...props}></Icon>
