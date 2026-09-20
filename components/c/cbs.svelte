<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwb03actr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwb03actr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cbs" {...props}></Icon>
