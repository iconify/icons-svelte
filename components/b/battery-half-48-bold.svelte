<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia0elbbtb.css';
import '../../css/z/zwjjpmnxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ia0elbbtb"/><path class="zwjjpmnxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-half-48-bold" {...props}></Icon>
