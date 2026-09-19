<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqzfn4-ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqzfn4-ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dripping-star" {...props}></Icon>
