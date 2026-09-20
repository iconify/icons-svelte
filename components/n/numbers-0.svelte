<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyqo3pdxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyqo3pdxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-0" {...props}></Icon>
