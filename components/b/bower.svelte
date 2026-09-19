<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfe2cdbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="cfe2cdbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bower" {...props}></Icon>
