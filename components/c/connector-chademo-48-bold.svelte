<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q668lybvz.css';
import '../../css/m/mmf760o5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q668lybvz"/><path class="mmf760o5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-chademo-48-bold" {...props}></Icon>
