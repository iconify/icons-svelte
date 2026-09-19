<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xot8q8bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xot8q8bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:brain" {...props}></Icon>
