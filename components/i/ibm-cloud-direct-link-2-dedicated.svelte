<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmiqepbty.css';
import '../../css/j/j7xllpb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qmiqepbty"/><path class="j7xllpb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-direct-link-2-dedicated" {...props}></Icon>
