<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7wwkf7up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7wwkf7up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-070" {...props}></Icon>
