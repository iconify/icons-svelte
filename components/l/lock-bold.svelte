<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9_8f-yfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9_8f-yfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-bold" {...props}></Icon>
