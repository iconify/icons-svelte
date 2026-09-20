<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4d7lfbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4d7lfbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:corner-up-left" {...props}></Icon>
