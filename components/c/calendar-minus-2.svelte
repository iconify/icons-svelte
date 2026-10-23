<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khe5ybbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khe5ybbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-minus-2" {...props}></Icon>
