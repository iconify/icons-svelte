<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij_mazs6p.css';
import '../../css/u/uaycyrbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ij_mazs6p"/><path class="uaycyrbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:media-changer-solid-alerted" {...props}></Icon>
