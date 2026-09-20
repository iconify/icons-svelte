<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvyhydbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvyhydbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-2-off" {...props}></Icon>
