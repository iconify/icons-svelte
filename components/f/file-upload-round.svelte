<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx73u_ukv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx73u_ukv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-upload-round" {...props}></Icon>
