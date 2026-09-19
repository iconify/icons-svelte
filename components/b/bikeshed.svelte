<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0ldy-bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="l0ldy-bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bikeshed" {...props}></Icon>
