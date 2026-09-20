<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tskkj_7-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tskkj_7-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opnsense-light" {...props}></Icon>
