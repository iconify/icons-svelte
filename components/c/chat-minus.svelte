<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orf635bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orf635bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-minus" {...props}></Icon>
