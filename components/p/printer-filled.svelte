<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmzgebbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kmzgebbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:printer-filled" {...props}></Icon>
