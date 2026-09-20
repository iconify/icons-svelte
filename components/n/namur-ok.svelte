<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if-aux86e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="if-aux86e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:namur-ok" {...props}></Icon>
