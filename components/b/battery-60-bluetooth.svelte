<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugiwfub4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugiwfub4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-60-bluetooth" {...props}></Icon>
