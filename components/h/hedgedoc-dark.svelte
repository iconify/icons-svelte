<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i08sjibyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i08sjibyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hedgedoc-dark" {...props}></Icon>
