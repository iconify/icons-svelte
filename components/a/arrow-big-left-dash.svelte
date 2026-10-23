<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd5fo2oke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd5fo2oke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-left-dash" {...props}></Icon>
