<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah4awdbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah4awdbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reply-all-fill" {...props}></Icon>
