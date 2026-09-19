<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajl8h9bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ajl8h9bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fexl" {...props}></Icon>
