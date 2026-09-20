<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr-_4lbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr-_4lbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-group" {...props}></Icon>
