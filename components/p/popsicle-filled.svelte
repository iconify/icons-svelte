<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iivu8_blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iivu8_blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:popsicle-filled" {...props}></Icon>
