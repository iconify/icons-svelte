<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6y3oxb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6y3oxb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paperclip-off" {...props}></Icon>
