<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp111nb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lp111nb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:greenhouse" {...props}></Icon>
