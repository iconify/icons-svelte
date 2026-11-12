<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wotd8qb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wotd8qb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quetre-light" {...props}></Icon>
