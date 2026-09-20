<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne5jje6vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne5jje6vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-frown-outline" {...props}></Icon>
