<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/ghelsvv_i.css';
import '../../css/k/k8ajql7ic.css';
import '../../css/h/hgh_uxb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="ghelsvv_i"/><path class="k8ajql7ic"/><path class="hgh_uxb8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:golang" {...props}></Icon>
