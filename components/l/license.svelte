<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofvt09bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ofvt09bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:license" {...props}></Icon>
