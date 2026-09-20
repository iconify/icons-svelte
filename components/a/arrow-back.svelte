<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1nuh0b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1nuh0b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-back" {...props}></Icon>
