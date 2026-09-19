<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2n6zrbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v2n6zrbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pm2" {...props}></Icon>
