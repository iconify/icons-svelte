<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am7a59n1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="am7a59n1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-minus-filled" {...props}></Icon>
