<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa0o18b5j.css';
import '../../css/a/argg3sbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fa0o18b5j"/><path class="argg3sbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:egg-48" {...props}></Icon>
