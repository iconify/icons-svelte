<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkme35pvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jkme35pvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:homeassistant" {...props}></Icon>
