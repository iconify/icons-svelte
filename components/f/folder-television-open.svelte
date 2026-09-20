<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtmc67bsf.css';
import '../../css/z/zaro8kx4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jtmc67bsf"/><path class="zaro8kx4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-television-open" {...props}></Icon>
