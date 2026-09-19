<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9-a-fbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9-a-fbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-053" {...props}></Icon>
