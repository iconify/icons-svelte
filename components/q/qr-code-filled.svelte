<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzv543hpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xzv543hpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:qr-code-filled" {...props}></Icon>
