<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl58pzhhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl58pzhhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:follow-fill" {...props}></Icon>
