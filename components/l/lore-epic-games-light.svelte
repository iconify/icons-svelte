<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm0lxtbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tm0lxtbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lore-epic-games-light" {...props}></Icon>
