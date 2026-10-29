<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axw66dbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axw66dbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-archive" {...props}></Icon>
