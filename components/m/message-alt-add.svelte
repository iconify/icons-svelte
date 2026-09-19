<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpr9a6b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpr9a6b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-alt-add" {...props}></Icon>
