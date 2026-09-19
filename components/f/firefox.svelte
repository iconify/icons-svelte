<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehapg43cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="ehapg43cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:firefox" {...props}></Icon>
