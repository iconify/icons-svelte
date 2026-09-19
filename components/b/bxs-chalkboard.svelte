<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx6s3u3tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mx6s3u3tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chalkboard" {...props}></Icon>
