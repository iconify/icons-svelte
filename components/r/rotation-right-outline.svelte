<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owy-2xwyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="owy-2xwyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:rotation-right-outline" {...props}></Icon>
