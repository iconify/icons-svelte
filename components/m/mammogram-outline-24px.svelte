<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2zpd4s6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2zpd4s6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mammogram-outline-24px" {...props}></Icon>
