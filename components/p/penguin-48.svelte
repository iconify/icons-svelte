<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wibsj_byf.css';
import '../../css/w/w303u3a6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wibsj_byf"/><path class="w303u3a6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:penguin-48" {...props}></Icon>
