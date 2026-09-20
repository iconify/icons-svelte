<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaa78xbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaa78xbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:globe-americas" {...props}></Icon>
