<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrk4ij8ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jrk4ij8ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hospital-24px" {...props}></Icon>
