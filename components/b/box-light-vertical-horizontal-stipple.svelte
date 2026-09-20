<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk3yrs-uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="uk3yrs-uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal-stipple" {...props}></Icon>
