<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-u9t_bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-u9t_bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dragon-shield" {...props}></Icon>
