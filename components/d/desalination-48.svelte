<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs7ozkfiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qs7ozkfiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desalination-48" {...props}></Icon>
