<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5qjvab8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5qjvab8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:egyptian-urns" {...props}></Icon>
