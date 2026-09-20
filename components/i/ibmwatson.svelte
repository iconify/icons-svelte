<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-8_uz2ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-8_uz2ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ibmwatson" {...props}></Icon>
