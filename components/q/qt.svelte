<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxn98bfaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxn98bfaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qt" {...props}></Icon>
