<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlpqz_bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vlpqz_bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:akka" {...props}></Icon>
