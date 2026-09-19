<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcmcnz_9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcmcnz_9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:heart-filled" {...props}></Icon>
