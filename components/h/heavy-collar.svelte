<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0etz709r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0etz709r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heavy-collar" {...props}></Icon>
