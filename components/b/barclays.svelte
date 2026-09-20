<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh1n3196e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh1n3196e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:barclays" {...props}></Icon>
