<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltdby2oqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ltdby2oqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:paint-bucket" {...props}></Icon>
