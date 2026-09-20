<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hf5strfwg.css';
import '../../css/m/m-15fobun.css';
import '../../css/m/m_3d8hblg.css';
import '../../css/o/oid2twx0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="hf5strfwg"/><path class="m-15fobun"/><path class="m_3d8hblg"/><path class="oid2twx0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:mongodb" {...props}></Icon>
