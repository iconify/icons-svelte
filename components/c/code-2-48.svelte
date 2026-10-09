<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkcr5wbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nkcr5wbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:code-2-48" {...props}></Icon>
