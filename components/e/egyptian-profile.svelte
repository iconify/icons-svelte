<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyx-81bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jyx-81bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:egyptian-profile" {...props}></Icon>
