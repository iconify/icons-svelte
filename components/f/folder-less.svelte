<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcjmcxbsc.css';
import '../../css/m/m_0djgu3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hcjmcxbsc"/><path class="m_0djgu3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-less" {...props}></Icon>
