<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ripyr9y3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ripyr9y3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:great-pyramid" {...props}></Icon>
