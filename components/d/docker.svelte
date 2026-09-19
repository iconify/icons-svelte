<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht1y7-bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="ht1y7-bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:docker" {...props}></Icon>
