<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czo4g_e8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czo4g_e8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loader-fill" {...props}></Icon>
