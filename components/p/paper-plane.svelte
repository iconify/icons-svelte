<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5y65zb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="a5y65zb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:paper-plane" {...props}></Icon>
