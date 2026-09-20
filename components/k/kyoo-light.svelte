<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n15170bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n15170bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kyoo-light" {...props}></Icon>
