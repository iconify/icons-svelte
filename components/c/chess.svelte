<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi_rclbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xi_rclbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:chess" {...props}></Icon>
