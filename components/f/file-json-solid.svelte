<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miq8s0bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miq8s0bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-json-solid" {...props}></Icon>
