<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s85qfinjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s85qfinjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:analytics-pie-3" {...props}></Icon>
