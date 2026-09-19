<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtx52bclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jtx52bclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:flyway" {...props}></Icon>
