<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapfr2bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qapfr2bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:candycane" {...props}></Icon>
