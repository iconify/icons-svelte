<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0lv3ob6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0lv3ob6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-unknow-fill" {...props}></Icon>
