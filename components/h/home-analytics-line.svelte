<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqxyuhbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqxyuhbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:home-analytics-line" {...props}></Icon>
