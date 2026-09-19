<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er594qb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="er594qb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battle-mech" {...props}></Icon>
