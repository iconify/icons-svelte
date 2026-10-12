<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shrbis3_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shrbis3_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:keyboard-filled" {...props}></Icon>
