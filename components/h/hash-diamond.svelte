<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir1wpry2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir1wpry2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hash-diamond" {...props}></Icon>
