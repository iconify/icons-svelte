<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcfax0boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcfax0boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alarm-clock-minus-line" {...props}></Icon>
