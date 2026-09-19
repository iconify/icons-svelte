<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm1u20b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sm1u20b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crystal-eye" {...props}></Icon>
