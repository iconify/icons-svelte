<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6z7a8-0d.css';
import '../../css/k/kebsqacsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6z7a8-0d"/><path class="kebsqacsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:mic-off-fill" {...props}></Icon>
