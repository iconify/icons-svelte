<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vurw64bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vurw64bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:awk" {...props}></Icon>
