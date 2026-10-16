<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elj7bpqnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="elj7bpqnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landfill-48" {...props}></Icon>
