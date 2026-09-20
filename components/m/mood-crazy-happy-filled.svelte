<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6afqrboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6afqrboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-crazy-happy-filled" {...props}></Icon>
