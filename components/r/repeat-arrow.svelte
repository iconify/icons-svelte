<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xucik59fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xucik59fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:repeat-arrow" {...props}></Icon>
