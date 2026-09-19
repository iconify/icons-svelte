<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x89aj3bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x89aj3bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:camera-filled" {...props}></Icon>
