<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqwamo7sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqwamo7sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-filled" {...props}></Icon>
