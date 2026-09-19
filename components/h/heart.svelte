<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyh0tabwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xyh0tabwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:heart" {...props}></Icon>
