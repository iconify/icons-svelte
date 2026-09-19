<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a56ac9v7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a56ac9v7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:meteor-impact" {...props}></Icon>
