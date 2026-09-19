<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f69w6uxsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f69w6uxsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:mortgage-filled" {...props}></Icon>
