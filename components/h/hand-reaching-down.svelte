<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/menb0t_lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="menb0t_lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hand-reaching-down" {...props}></Icon>
