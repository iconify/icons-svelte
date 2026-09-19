<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy_-jrb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cy_-jrb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:conversation" {...props}></Icon>
