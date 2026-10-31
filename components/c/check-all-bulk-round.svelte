<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0pkalbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0pkalbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:check-all-bulk-round" {...props}></Icon>
