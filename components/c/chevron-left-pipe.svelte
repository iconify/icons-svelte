<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s40lrccni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s40lrccni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chevron-left-pipe" {...props}></Icon>
