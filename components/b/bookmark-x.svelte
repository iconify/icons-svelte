<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugma2jbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugma2jbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bookmark-x" {...props}></Icon>
