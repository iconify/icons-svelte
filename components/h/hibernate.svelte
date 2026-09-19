<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfw9hvbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yfw9hvbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:hibernate" {...props}></Icon>
