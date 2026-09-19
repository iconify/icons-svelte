<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z49akjbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="z49akjbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:holly-berry" {...props}></Icon>
