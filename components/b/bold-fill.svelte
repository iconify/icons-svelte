<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsntm0bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsntm0bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bold-fill" {...props}></Icon>
