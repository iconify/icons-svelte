<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g2by2f8cm.css';
import '../../css/r/r-lr4020s.css';
import '../../css/o/oochcfc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g2by2f8cm"/><path class="r-lr4020s"/><path class="oochcfc2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cuboid-duotone" {...props}></Icon>
