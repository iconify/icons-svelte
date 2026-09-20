<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6-qsdc1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-qsdc1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:h-6" {...props}></Icon>
