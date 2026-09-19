<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiq7q7toc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tiq7q7toc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clothespin" {...props}></Icon>
