<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovg9qx-rh.css';
import '../../css/i/iz8c3l5-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovg9qx-rh"/><path class="iz8c3l5-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-search-duotone" {...props}></Icon>
