<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad3vngbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad3vngbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-left-circle" {...props}></Icon>
