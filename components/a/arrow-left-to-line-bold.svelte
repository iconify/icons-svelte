<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmh9szrbi.css';
import '../../css/g/gmic3ry4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmh9szrbi"/><path class="gmic3ry4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-to-line-bold" {...props}></Icon>
