<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf8aa8b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lf8aa8b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin-stars" {...props}></Icon>
