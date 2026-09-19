<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn4yg_1oe.css';
import '../../css/l/lsp0zwf3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sn4yg_1oe"/><path class="lsp0zwf3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ember" {...props}></Icon>
