<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noegfwg_l.css';
import '../../css/r/r-a7fhb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="noegfwg_l"/><path class="r-a7fhb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:mental-health" {...props}></Icon>
