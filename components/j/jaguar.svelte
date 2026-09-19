<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhb8habpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhb8habpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:jaguar" {...props}></Icon>
