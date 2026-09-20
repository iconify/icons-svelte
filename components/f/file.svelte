<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hue27w-ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hue27w-ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:file" {...props}></Icon>
