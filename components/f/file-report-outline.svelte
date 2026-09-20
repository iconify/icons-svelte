<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z59vie_hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z59vie_hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-report-outline" {...props}></Icon>
