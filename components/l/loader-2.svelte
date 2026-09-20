<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs7v3hkcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs7v3hkcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:loader-2" {...props}></Icon>
