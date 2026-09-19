<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnd4yka7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<rect transform="translate(0 947.638)" class="lnd4yka7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:call-activity" {...props}></Icon>
