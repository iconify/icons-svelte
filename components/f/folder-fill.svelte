<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb2412y3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb2412y3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-fill" {...props}></Icon>
