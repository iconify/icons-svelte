<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5inc_bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5inc_bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pilcrow" {...props}></Icon>
