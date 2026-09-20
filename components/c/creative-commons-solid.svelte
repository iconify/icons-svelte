<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6uk2fb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s6uk2fb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:creative-commons-solid" {...props}></Icon>
