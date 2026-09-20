<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbdm09g-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbdm09g-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:codesandbox" {...props}></Icon>
