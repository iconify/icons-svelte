<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2qtbkbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2qtbkbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder-minus-filled" {...props}></Icon>
