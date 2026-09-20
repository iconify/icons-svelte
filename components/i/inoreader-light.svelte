<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5db48gif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5db48gif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inoreader-light" {...props}></Icon>
