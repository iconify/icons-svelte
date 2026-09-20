<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3eh006vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3eh006vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fortinet" {...props}></Icon>
