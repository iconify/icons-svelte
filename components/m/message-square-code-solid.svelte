<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi1fe2btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi1fe2btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-code-solid" {...props}></Icon>
