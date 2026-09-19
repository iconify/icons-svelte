<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5llm5iqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5llm5iqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-security-light" {...props}></Icon>
