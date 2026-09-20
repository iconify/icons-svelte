<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3gs0pbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3gs0pbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:powershell" {...props}></Icon>
