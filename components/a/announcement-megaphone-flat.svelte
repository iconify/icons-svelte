<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wc9nglaeh.css';
import '../../css/v/v_k9vr9md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wc9nglaeh"/><path class="v_k9vr9md"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:announcement-megaphone-flat" {...props}></Icon>
