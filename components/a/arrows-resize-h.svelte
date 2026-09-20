<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmpdzvbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmpdzvbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-resize-h" {...props}></Icon>
