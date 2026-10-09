<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddna9niwb.css';
import '../../css/g/g2r0sac-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ddna9niwb"/><path class="g2r0sac-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:palette-48" {...props}></Icon>
