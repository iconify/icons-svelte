<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdk7ydjke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hdk7ydjke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nodered" {...props}></Icon>
