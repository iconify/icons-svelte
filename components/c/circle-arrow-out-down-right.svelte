<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrr2qmbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrr2qmbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-arrow-out-down-right" {...props}></Icon>
