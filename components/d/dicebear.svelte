<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or9g_jxky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or9g_jxky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dicebear" {...props}></Icon>
