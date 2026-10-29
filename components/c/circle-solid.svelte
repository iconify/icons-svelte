<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkf82twio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkf82twio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-solid" {...props}></Icon>
