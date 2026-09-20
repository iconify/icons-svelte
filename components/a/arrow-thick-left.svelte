<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2xd09b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e2xd09b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:arrow-thick-left" {...props}></Icon>
