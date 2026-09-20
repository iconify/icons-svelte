<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg_cwepzi.css';
import '../../css/t/tvqx1abby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sg_cwepzi"/><path class="tvqx1abby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-stack-open" {...props}></Icon>
