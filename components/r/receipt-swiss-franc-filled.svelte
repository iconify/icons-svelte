<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl6ol6zfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl6ol6zfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:receipt-swiss-franc-filled" {...props}></Icon>
