<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqumaeb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qqumaeb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nestjs" {...props}></Icon>
