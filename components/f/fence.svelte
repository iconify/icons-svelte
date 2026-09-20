<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi0g_w8en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi0g_w8en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:fence" {...props}></Icon>
