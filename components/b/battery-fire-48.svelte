<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuqr6acyi.css';
import '../../css/b/bp937cc8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iuqr6acyi"/><path class="bp937cc8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-fire-48" {...props}></Icon>
