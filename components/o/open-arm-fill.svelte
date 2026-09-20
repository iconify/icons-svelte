<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5us7hf0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5us7hf0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:open-arm-fill" {...props}></Icon>
