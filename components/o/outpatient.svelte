<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry477xb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ry477xb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:outpatient" {...props}></Icon>
