<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okl2atbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okl2atbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:activity-heartbeat" {...props}></Icon>
