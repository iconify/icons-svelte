<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joamw7nrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="joamw7nrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:falling" {...props}></Icon>
