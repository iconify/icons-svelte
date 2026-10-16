<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6gupfjay.css';
import '../../css/j/j7hxfr2_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g6gupfjay"/><path class="j7hxfr2_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-sink-48" {...props}></Icon>
