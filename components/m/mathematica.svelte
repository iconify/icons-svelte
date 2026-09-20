<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogt4byurq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="ogt4byurq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:mathematica" {...props}></Icon>
