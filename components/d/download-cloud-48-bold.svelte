<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbb-tygif.css';
import '../../css/i/iry5se_sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bbb-tygif"/><path class="iry5se_sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:download-cloud-48-bold" {...props}></Icon>
