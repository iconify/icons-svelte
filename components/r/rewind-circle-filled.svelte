<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laxrx2gyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laxrx2gyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rewind-circle-filled" {...props}></Icon>
