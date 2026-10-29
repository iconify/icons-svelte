<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlejs_b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlejs_b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-text" {...props}></Icon>
