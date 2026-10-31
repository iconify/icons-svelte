<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h083lj9da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h083lj9da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cookie-round" {...props}></Icon>
