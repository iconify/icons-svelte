<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsqm2vbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsqm2vbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-code-2-filled" {...props}></Icon>
