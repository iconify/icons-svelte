<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdh48zxjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gdh48zxjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brightness-3" {...props}></Icon>
