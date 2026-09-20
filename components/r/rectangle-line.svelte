<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt6iyeqqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt6iyeqqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rectangle-line" {...props}></Icon>
