<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwzz2zy_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwzz2zy_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:diving-helmet" {...props}></Icon>
