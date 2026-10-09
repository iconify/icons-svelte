<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjpipuzmt.css';
import '../../css/g/g73cn62ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fjpipuzmt"/><path class="g73cn62ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:doorbell-48" {...props}></Icon>
