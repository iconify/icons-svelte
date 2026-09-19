<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic72lyaaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":46,"height":80};
const content = `<path class="ic72lyaaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:draghandle" {...props}></Icon>
