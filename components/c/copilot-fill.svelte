<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwxmvn-7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwxmvn-7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:copilot-fill" {...props}></Icon>
