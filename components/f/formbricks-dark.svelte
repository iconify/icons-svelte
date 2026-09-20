<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8_04vsma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8_04vsma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:formbricks-dark" {...props}></Icon>
