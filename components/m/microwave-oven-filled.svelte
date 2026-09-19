<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmt3mh2kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmt3mh2kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microwave-oven-filled" {...props}></Icon>
