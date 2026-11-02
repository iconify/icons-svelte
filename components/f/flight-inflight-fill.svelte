<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qax5_jh4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qax5_jh4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flight-inflight-fill" {...props}></Icon>
