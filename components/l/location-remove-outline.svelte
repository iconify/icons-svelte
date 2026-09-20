<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcw6cxbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcw6cxbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-remove-outline" {...props}></Icon>
