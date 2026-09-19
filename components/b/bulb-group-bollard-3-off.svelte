<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izuh8ib-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izuh8ib-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-bollard-3-off" {...props}></Icon>
