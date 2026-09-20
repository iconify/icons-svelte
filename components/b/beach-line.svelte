<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhe1fhbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhe1fhbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:beach-line" {...props}></Icon>
