<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fm9vtkb7w.css';
import '../../css/e/e3_eq5b9n.css';
import '../../css/y/ynivx94-x.css';
import '../../css/r/r7ac2ob5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect class="fm9vtkb7w"/><rect class="e3_eq5b9n"/><rect class="ynivx94-x"/><path class="r7ac2ob5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:network" {...props}></Icon>
