<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij-djlcqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ij-djlcqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arc-third-20-solid" {...props}></Icon>
