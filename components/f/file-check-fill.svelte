<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz67vh9ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz67vh9ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-check-fill" {...props}></Icon>
