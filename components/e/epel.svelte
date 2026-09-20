<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmohik-ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmohik-ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:epel" {...props}></Icon>
