<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjy91kbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjy91kbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:macro-filled" {...props}></Icon>
