<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny8rlnbhx.css';
import '../../css/o/o684edcxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ny8rlnbhx"/><path class="o684edcxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamtx" {...props}></Icon>
