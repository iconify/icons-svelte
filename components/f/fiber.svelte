<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf_vahzfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gf_vahzfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:fiber" {...props}></Icon>
