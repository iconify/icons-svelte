<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voq8q4hpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voq8q4hpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-echarts" {...props}></Icon>
