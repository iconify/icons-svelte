<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihhxc7j7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihhxc7j7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lore-epic-games-dark" {...props}></Icon>
