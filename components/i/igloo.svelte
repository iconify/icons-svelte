<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-r93_b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-r93_b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:igloo" {...props}></Icon>
