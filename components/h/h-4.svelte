<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvky8xb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvky8xb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:h-4" {...props}></Icon>
