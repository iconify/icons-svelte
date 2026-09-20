<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_p2g0bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_p2g0bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:briefcase-line" {...props}></Icon>
