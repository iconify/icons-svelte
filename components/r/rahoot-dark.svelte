<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-5xqh4-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-5xqh4-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rahoot-dark" {...props}></Icon>
