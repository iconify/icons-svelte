<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3e-t01qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3e-t01qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-rounded-x" {...props}></Icon>
