<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1v07ne6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1v07ne6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-bag-crumpled" {...props}></Icon>
