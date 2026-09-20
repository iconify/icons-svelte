<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_-kcvb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_-kcvb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hard-drive-fill" {...props}></Icon>
