<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cojdnpbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cojdnpbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nals" {...props}></Icon>
