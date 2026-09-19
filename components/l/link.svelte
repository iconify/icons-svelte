<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2s445iid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2s445iid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:link" {...props}></Icon>
