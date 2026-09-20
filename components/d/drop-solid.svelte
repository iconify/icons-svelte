<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou-24ml_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou-24ml_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:drop-solid" {...props}></Icon>
