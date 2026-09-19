<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ollmjwbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ollmjwbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:express" {...props}></Icon>
