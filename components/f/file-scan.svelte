<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew2vtpdse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew2vtpdse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-scan" {...props}></Icon>
