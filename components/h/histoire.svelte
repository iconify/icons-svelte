<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuq04pbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kuq04pbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:histoire" {...props}></Icon>
