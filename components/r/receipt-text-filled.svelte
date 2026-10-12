<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifcnitjmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifcnitjmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:receipt-text-filled" {...props}></Icon>
