<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf-ng2b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-ng2b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:marigold-solid" {...props}></Icon>
