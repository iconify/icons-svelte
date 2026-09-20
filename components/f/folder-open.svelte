<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p86ew9b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p86ew9b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:folder-open" {...props}></Icon>
