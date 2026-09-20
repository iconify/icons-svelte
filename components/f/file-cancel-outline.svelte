<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-6j63-le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-6j63-le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-cancel-outline" {...props}></Icon>
