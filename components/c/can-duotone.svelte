<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/osa774bht.css';
import '../../css/y/yh1jv4bwi.css';
import '../../css/r/r0ymitb5z.css';
import '../../css/y/ygm0plb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="osa774bht"/><path class="yh1jv4bwi"/><path class="r0ymitb5z"/><path class="ygm0plb9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:can-duotone" {...props}></Icon>
