<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cve7h0b7y.css';
import '../../css/r/rb36fjzyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cve7h0b7y"/><path class="rb36fjzyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:feather-filled" {...props}></Icon>
