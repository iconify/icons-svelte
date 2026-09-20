<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj90mebhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zj90mebhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piefed-dark" {...props}></Icon>
