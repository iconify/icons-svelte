<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1k692o9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1k692o9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:at-t-light" {...props}></Icon>
