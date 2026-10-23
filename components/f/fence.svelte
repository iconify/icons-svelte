<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8mx1cb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8mx1cb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:fence" {...props}></Icon>
