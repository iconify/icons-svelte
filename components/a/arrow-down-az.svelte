<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fybz9cc9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fybz9cc9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-down-az" {...props}></Icon>
