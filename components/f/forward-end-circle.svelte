<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2_z2v3wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2_z2v3wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:forward-end-circle" {...props}></Icon>
