<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic7o1nb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ic7o1nb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-116" {...props}></Icon>
