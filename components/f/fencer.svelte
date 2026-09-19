<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrgkuqb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jrgkuqb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fencer" {...props}></Icon>
