<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt5ganbfh.css';
import '../../css/t/tqowt8nqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt5ganbfh"/><path class="tqowt8nqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pallete-2-bold-duotone" {...props}></Icon>
