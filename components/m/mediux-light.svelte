<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkfanx12o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nkfanx12o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediux-light" {...props}></Icon>
