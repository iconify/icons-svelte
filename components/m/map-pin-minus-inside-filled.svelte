<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzgrr6crx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzgrr6crx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-minus-inside-filled" {...props}></Icon>
