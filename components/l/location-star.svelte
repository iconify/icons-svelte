<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceqlhwbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceqlhwbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-star" {...props}></Icon>
