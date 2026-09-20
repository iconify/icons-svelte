<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztm_71buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztm_71buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-copy-2-fill" {...props}></Icon>
