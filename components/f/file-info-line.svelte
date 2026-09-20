<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn3kvq7mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn3kvq7mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-info-line" {...props}></Icon>
