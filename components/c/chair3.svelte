<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es4zrthkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es4zrthkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chair3" {...props}></Icon>
