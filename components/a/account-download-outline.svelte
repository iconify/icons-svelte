<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juk_1pbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juk_1pbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-download-outline" {...props}></Icon>
