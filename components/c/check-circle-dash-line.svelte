<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4kt-3w1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4kt-3w1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-circle-dash-line" {...props}></Icon>
