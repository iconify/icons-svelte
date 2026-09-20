<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzijn6bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzijn6bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-intermediate-variant" {...props}></Icon>
