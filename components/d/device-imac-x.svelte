<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i68s3xu0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i68s3xu0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-x" {...props}></Icon>
