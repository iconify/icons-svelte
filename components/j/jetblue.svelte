<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yet3i3p8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yet3i3p8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jetblue" {...props}></Icon>
