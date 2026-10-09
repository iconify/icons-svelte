<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3wq640fi.css';
import '../../css/x/x59ggbc2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m3wq640fi"/><path class="x59ggbc2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hanger-48" {...props}></Icon>
