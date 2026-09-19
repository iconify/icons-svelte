<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsp-l3m4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":957,"height":1024};
const content = `<path class="lsp-l3m4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dialpad" {...props}></Icon>
