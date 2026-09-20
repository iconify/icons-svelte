<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjx_55mtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zjx_55mtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:navigation-arrow-on" {...props}></Icon>
