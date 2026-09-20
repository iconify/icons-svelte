<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6k178ekp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6k178ekp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chatbot" {...props}></Icon>
