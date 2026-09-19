<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsep9da-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsep9da-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:document-remove" {...props}></Icon>
