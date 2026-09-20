<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inb6nib5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inb6nib5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-minus" {...props}></Icon>
