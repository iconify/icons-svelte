<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np0p-h43r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np0p-h43r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pencil-sparkles-filled" {...props}></Icon>
