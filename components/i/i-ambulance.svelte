<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5wn405-h.css';
import '../../css/b/bed8vacuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="d5wn405-h"/><path class="bed8vacuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-ambulance" {...props}></Icon>
