<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roy_pgb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="roy_pgb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:orchid-mahjong" {...props}></Icon>
