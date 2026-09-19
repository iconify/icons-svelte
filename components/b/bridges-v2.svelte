<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3k-2m9tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3k-2m9tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bridges-v2" {...props}></Icon>
