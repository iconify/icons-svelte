<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5u8ltlqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5u8ltlqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-hello-variant" {...props}></Icon>
