<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zolay6gvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zolay6gvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:briefcase-medical" {...props}></Icon>
