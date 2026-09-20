<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdw66-bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdw66-bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:napster" {...props}></Icon>
