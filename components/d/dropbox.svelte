<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7dn_sbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":464};
const content = `<path class="x7dn_sbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dropbox" {...props}></Icon>
