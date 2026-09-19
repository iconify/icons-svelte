<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd3i6ixgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd3i6ixgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:database" {...props}></Icon>
