<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soui-00bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="soui-00bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crt-sh-dark" {...props}></Icon>
