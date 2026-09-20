<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx2_3irej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zx2_3irej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-left-outline" {...props}></Icon>
