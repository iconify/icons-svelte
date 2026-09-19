<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5pmcac8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5pmcac8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hypersonic-bolt" {...props}></Icon>
