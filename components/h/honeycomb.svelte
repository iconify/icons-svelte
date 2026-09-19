<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o90xa617f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o90xa617f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:honeycomb" {...props}></Icon>
