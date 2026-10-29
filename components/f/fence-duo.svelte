<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s2gz3mbzi.css';
import '../../css/m/mexbxv5go.css';
import '../../css/s/s53jcxmyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s2gz3mbzi"/><path class="mexbxv5go wm-a"/><path class="s53jcxmyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fence-duo" {...props}></Icon>
