<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_yhftbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_yhftbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-image-outline" {...props}></Icon>
