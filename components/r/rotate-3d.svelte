<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq4wbcy9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq4wbcy9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rotate-3d" {...props}></Icon>
