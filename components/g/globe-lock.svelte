<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km7z8w6gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km7z8w6gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:globe-lock" {...props}></Icon>
