<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0u_c95tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k0u_c95tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nestjs" {...props}></Icon>
