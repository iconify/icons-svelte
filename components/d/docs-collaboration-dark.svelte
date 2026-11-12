<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztsqtcrhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ztsqtcrhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docs-collaboration-dark" {...props}></Icon>
