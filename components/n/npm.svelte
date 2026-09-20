<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8nci6b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8nci6b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:npm" {...props}></Icon>
