<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy3zah5lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy3zah5lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:accessibility-filled" {...props}></Icon>
