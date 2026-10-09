<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmjswi96d.css';
import '../../css/h/hz6q229uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mmjswi96d"/><path class="hz6q229uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dollar-20-bold" {...props}></Icon>
