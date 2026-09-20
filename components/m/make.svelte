<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm34tibrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm34tibrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:make" {...props}></Icon>
