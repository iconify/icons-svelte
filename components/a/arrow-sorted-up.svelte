<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbrld-b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbrld-b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-sorted-up" {...props}></Icon>
