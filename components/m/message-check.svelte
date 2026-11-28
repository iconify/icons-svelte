<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8xdwjqzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8xdwjqzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-check" {...props}></Icon>
