<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it8xc7b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it8xc7b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-exclamation-filled" {...props}></Icon>
