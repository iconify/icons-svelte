<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6576bc0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6576bc0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:heart-rate" {...props}></Icon>
