<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tot-1lbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tot-1lbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gift-filled" {...props}></Icon>
