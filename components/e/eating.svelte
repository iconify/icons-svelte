<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utb9ql0jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="utb9ql0jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eating" {...props}></Icon>
