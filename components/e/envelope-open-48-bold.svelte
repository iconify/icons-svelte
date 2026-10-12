<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8b9igb2o.css';
import '../../css/d/d3c0vccgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v8b9igb2o"/><path class="d3c0vccgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:envelope-open-48-bold" {...props}></Icon>
