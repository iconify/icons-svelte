<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuv5mcb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iuv5mcb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:copy-fill" {...props}></Icon>
