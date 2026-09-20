<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2b3s_9dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2b3s_9dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-2-bold" {...props}></Icon>
