<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhidz8epn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bhidz8epn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:macvim" {...props}></Icon>
