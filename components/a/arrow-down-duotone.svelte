<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz2kdjbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz2kdjbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-duotone" {...props}></Icon>
