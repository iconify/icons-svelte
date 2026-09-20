<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/d/dfzz3w77i.css';
import '../../css/p/pupt13zxe.css';
import '../../css/o/oj9-3vb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path class="dfzz3w77i"/><path class="pupt13zxe"/><path class="oj9-3vb9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:blender-dark" {...props}></Icon>
