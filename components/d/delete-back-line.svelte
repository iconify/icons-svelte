<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8ztbcb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8ztbcb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:delete-back-line" {...props}></Icon>
