<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9s-2fmsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9s-2fmsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:grid-fill" {...props}></Icon>
