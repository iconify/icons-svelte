<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k950p1_0a.css';
import '../../css/o/ojq_ufb-f.css';
import '../../css/y/y1y13wojh.css';
import '../../css/s/s3sx6db1y.css';
import '../../css/i/ih6ul4l0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVGER8ssbjM"><path class="k950p1_0a"/></clipPath></defs><g clip-path="url(#SVGER8ssbjM)" transform="translate(-256 -12.3)scale(1.024)"><path class="ojq_ufb-f"/><path class="y1y13wojh"/><path class="s3sx6db1y"/><path class="ih6ul4l0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ly-1x1" {...props}></Icon>
