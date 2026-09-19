<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx62a9nxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx62a9nxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pill-drop" {...props}></Icon>
