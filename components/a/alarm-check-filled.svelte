<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_b4k_bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g_b4k_bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alarm-check-filled" {...props}></Icon>
