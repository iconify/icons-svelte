<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvxlh2xex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvxlh2xex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:low-vision-filled" {...props}></Icon>
