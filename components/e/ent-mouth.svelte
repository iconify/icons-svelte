<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxrn6gb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxrn6gb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ent-mouth" {...props}></Icon>
