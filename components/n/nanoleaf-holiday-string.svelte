<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhr80pw9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhr80pw9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-holiday-string" {...props}></Icon>
