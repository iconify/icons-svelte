<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne8-4acba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ne8-4acba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:brush" {...props}></Icon>
