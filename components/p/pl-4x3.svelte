<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/damb695lr.css';
import '../../css/g/gwkoec6sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="d2kvgvbvc"><path class="damb695lr"/><path class="gwkoec6sp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:pl-4x3" {...props}></Icon>
