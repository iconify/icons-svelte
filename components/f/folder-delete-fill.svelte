<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx83m75qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx83m75qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-delete-fill" {...props}></Icon>
