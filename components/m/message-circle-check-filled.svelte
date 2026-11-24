<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r03x_bbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r03x_bbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-check-filled" {...props}></Icon>
