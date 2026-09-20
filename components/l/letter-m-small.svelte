<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xewb970xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xewb970xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-m-small" {...props}></Icon>
