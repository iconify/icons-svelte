<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad0u0jetp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad0u0jetp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-vertical-fill-round" {...props}></Icon>
