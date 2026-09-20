<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvpz_acxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvpz_acxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:glass-martini-alt" {...props}></Icon>
