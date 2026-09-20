<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxxw5db8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxxw5db8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-line-style" {...props}></Icon>
