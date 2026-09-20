<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7h63_brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7h63_brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-add-outline" {...props}></Icon>
