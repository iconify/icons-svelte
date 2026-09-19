<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6x_aab7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6x_aab7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:link-break-filled" {...props}></Icon>
