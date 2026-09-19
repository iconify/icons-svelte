<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a072lo8qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a072lo8qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:horseshoe" {...props}></Icon>
