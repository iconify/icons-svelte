<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf7059b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rf7059b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:alipay-small" {...props}></Icon>
