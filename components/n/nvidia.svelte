<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmx6tkb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmx6tkb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:nvidia" {...props}></Icon>
