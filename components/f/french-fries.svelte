<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-0-_geiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-0-_geiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:french-fries" {...props}></Icon>
