<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvrlecb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xvrlecb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:chevron-right" {...props}></Icon>
