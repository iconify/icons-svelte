<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjevk5tdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rjevk5tdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:child-48" {...props}></Icon>
