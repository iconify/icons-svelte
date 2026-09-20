<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/far2fhbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="far2fhbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:box-2-line" {...props}></Icon>
