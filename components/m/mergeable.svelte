<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5wzb1xmq.css';
import '../../css/q/q3gqlvbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5wzb1xmq"/><path class="q3gqlvbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mergeable" {...props}></Icon>
