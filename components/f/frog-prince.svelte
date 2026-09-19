<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopl69-zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gopl69-zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:frog-prince" {...props}></Icon>
