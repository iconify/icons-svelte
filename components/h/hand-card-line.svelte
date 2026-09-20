<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh7vy4bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh7vy4bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-card-line" {...props}></Icon>
