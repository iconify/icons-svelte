<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrukklbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrukklbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:inbox-unarchive-line" {...props}></Icon>
