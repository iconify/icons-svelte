<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvkgehx6a.css';
import '../../css/f/fo-j22b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jvkgehx6a"/><path class="fo-j22b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bathtub-48" {...props}></Icon>
