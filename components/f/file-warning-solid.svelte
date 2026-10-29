<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sda09p25t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sda09p25t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-warning-solid" {...props}></Icon>
