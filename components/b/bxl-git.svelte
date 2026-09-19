<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_renxgyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_renxgyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-git" {...props}></Icon>
