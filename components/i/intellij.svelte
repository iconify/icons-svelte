<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewef_zbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ewef_zbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:intellij" {...props}></Icon>
