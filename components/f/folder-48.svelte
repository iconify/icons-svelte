<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb9x9-c_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mb9x9-c_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-48" {...props}></Icon>
