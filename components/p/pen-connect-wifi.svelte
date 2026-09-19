<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhw5u9d6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhw5u9d6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pen-connect-wifi" {...props}></Icon>
