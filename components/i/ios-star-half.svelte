<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if3rg7blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="if3rg7blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-star-half" {...props}></Icon>
