<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh0o9zc1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh0o9zc1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:fold-horizontal" {...props}></Icon>
