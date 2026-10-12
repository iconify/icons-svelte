<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5i5m5e2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y5i5m5e2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-code-filled" {...props}></Icon>
