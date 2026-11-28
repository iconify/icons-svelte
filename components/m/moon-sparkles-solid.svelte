<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_9ku4bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_9ku4bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:moon-sparkles-solid" {...props}></Icon>
