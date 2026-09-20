<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haxd8wxpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haxd8wxpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-phone-line" {...props}></Icon>
