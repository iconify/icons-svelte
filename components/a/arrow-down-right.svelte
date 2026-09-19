<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx63t23tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx63t23tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:arrow-down-right" {...props}></Icon>
