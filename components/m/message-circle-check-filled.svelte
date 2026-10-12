<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdrs85b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdrs85b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-check-filled" {...props}></Icon>
