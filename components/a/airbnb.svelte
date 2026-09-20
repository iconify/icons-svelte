<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7t_hc8su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7t_hc8su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:airbnb" {...props}></Icon>
