<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgg2hac1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dgg2hac1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:opencv" {...props}></Icon>
