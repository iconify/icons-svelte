<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaax5ob0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaax5ob0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-badge-right-filled" {...props}></Icon>
