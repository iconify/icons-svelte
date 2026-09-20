<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmevz-btj.css';
import '../../css/o/oynab6bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bmevz-btj"/><path class="oynab6bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:roblox" {...props}></Icon>
