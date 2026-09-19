<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffi5e5btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffi5e5btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:neutral-face-fill" {...props}></Icon>
