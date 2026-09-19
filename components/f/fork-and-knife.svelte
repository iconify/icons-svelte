<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr13y7_yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yr13y7_yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:fork-and-knife" {...props}></Icon>
