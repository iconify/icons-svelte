<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsn3v9b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xsn3v9b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:beer-mug" {...props}></Icon>
