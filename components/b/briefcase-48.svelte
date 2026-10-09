<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chwqx0x_b.css';
import '../../css/f/fm25kwqqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="chwqx0x_b"/><path class="fm25kwqqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:briefcase-48" {...props}></Icon>
