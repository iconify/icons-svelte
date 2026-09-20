<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inm7k4bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inm7k4bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:linkedin" {...props}></Icon>
