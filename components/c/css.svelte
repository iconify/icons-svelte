<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dyanzub4e.css';
import '../../css/u/udx94hb3b.css';
import '../../css/o/oenk4v16u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="dyanzub4e"/><path class="udx94hb3b"/><path class="oenk4v16u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:css" {...props}></Icon>
