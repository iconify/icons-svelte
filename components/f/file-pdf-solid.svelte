<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni3q_32ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni3q_32ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-pdf-solid" {...props}></Icon>
