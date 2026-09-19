<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p67v0bc-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p67v0bc-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jsx-alt" {...props}></Icon>
