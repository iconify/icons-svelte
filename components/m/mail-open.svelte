<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsuqk849p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsuqk849p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mail-open" {...props}></Icon>
