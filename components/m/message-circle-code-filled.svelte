<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry2_e2bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ry2_e2bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-code-filled" {...props}></Icon>
