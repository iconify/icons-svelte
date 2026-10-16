<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvdhc8bfy.css';
import '../../css/d/dnfd7hb8j.css';
import '../../css/p/pd5-qwbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hvdhc8bfy"/><path class="dnfd7hb8j"/><path class="pd5-qwbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-health-48" {...props}></Icon>
