<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h52vambzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h52vambzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kid-slide" {...props}></Icon>
