<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flgd7161p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="flgd7161p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carton-filled" {...props}></Icon>
