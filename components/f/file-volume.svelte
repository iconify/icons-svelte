<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adkf8dbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adkf8dbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-volume" {...props}></Icon>
