<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n9qsr0bsc.css';
import '../../css/p/ptoawcs-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n9qsr0bsc"/><path clip-rule="evenodd" class="ptoawcs-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:battery-empty-2-flat" {...props}></Icon>
