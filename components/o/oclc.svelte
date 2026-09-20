<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg0-37bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg0-37bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oclc" {...props}></Icon>
