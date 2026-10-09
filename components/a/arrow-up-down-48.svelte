<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a92d54b2y.css';
import '../../css/h/hubseccej.css';
import '../../css/v/vl5abyl6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a92d54b2y"/><path class="hubseccej"/><path class="vl5abyl6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-down-48" {...props}></Icon>
