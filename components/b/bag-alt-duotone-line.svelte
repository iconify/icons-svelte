<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kkkulc1_f.css';
import '../../css/o/opmwddc4w.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGmLoa2ckR"><g class="ft5dv1b6b"><path class="kkkulc1_f"/><path class="opmwddc4w"/></g></mask></defs><path mask="url(#SVGmLoa2ckR)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bag-alt-duotone-line" {...props}></Icon>
