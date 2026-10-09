<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8ue7ubrb.css';
import '../../css/o/o_kxisbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l8ue7ubrb"/><path class="o_kxisbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forecast-48-bold" {...props}></Icon>
