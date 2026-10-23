<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syplbccnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syplbccnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panel-left" {...props}></Icon>
