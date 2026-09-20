<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz-3upcrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jz-3upcrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eye-closed-bold" {...props}></Icon>
