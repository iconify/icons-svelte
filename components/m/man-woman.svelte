<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt8u25aon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt8u25aon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:man-woman" {...props}></Icon>
