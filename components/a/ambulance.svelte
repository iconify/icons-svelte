<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6vlwn-dd.css';
import '../../css/x/xmq-usnto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6vlwn-dd"/><path class="xmq-usnto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ambulance" {...props}></Icon>
