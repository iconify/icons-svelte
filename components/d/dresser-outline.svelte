<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u64wme6op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u64wme6op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dresser-outline" {...props}></Icon>
