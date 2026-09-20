<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbt-of79j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbt-of79j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:chart-network-solid" {...props}></Icon>
