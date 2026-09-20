<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alhq8vbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alhq8vbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluesky-social-fill" {...props}></Icon>
