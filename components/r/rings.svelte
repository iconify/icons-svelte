<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt537krfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt537krfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rings" {...props}></Icon>
