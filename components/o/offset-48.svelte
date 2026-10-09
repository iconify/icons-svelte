<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii9mn0isr.css';
import '../../css/w/whuwc1eqk.css';
import '../../css/c/cmlaleo2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ii9mn0isr"/><path class="whuwc1eqk"/><path class="cmlaleo2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offset-48" {...props}></Icon>
