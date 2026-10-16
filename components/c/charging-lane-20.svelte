<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwqc3bbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gwqc3bbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-lane-20" {...props}></Icon>
