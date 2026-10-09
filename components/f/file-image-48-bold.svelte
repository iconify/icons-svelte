<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdos38jip.css';
import '../../css/k/kcfd8k4na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pdos38jip"/><path class="kcfd8k4na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-image-48-bold" {...props}></Icon>
