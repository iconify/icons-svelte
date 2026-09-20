<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5zr_9r_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5zr_9r_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-lock-outline" {...props}></Icon>
