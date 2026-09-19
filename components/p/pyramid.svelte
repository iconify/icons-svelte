<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm4wkjbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm4wkjbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pyramid" {...props}></Icon>
