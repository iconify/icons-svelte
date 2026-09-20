<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu5s-5d2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zu5s-5d2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bagisto-light" {...props}></Icon>
