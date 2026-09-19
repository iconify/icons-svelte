<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm7pf2ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vm7pf2ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plus-duo" {...props}></Icon>
