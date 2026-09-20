<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr4dnob2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tr4dnob2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:medical-cross-sign-healthcare-flat" {...props}></Icon>
