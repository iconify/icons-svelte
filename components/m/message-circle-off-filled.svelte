<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtlkh7b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtlkh7b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-off-filled" {...props}></Icon>
