<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7gn9tbal.css';
import '../../css/g/g2_udexnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7gn9tbal"/><path class="g2_udexnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbon-bold" {...props}></Icon>
