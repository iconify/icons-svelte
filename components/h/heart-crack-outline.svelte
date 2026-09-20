<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqgochbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqgochbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-crack-outline" {...props}></Icon>
