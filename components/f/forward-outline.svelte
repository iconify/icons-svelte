<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dneqsibml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dneqsibml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:forward-outline" {...props}></Icon>
