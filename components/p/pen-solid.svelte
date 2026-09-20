<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2r483b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2r483b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pen-solid" {...props}></Icon>
