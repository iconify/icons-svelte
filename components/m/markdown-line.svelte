<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7_pyqfau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7_pyqfau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:markdown-line" {...props}></Icon>
