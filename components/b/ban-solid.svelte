<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3sn4wb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3sn4wb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ban-solid" {...props}></Icon>
