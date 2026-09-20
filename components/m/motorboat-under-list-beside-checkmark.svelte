<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wozpvq2zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wozpvq2zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-under-list-beside-checkmark" {...props}></Icon>
