<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4c4oxb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="r4c4oxb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:mdb" {...props}></Icon>
