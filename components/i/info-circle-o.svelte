<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_9zuben.css';
import '../../css/k/kd27g93zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vd_9zuben"/><path class="kd27g93zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:info-circle-o" {...props}></Icon>
