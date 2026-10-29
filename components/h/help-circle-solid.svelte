<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adpz3lbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adpz3lbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:help-circle-solid" {...props}></Icon>
