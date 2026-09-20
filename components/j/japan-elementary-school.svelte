<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ili0bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q7ili0bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:japan-elementary-school" {...props}></Icon>
