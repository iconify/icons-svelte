<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvnrk-_wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvnrk-_wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:chevron-down" {...props}></Icon>
