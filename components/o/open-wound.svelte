<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojkue2tvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojkue2tvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:open-wound" {...props}></Icon>
