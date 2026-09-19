<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdw3qmbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdw3qmbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-071" {...props}></Icon>
