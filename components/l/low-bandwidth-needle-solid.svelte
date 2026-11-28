<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmv4wkb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmv4wkb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:low-bandwidth-needle-solid" {...props}></Icon>
