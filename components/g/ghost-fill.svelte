<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3prxeb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3prxeb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ghost-fill" {...props}></Icon>
