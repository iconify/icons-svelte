<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acc9x56xd.css';
import '../../css/q/qj8k73bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="acc9x56xd"/><path class="qj8k73bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gallery-48" {...props}></Icon>
