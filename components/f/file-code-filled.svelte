<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv4h2bcjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv4h2bcjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-code-filled" {...props}></Icon>
