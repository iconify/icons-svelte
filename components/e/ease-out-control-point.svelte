<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcr-_t1sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcr-_t1sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ease-out-control-point" {...props}></Icon>
