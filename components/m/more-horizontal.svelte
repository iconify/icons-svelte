<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny2g-5bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny2g-5bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:more-horizontal" {...props}></Icon>
