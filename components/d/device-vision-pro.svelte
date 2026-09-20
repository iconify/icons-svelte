<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j61x_kapz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j61x_kapz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-vision-pro" {...props}></Icon>
