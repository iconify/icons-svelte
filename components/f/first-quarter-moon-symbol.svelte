<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftu8mvbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ftu8mvbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:first-quarter-moon-symbol" {...props}></Icon>
