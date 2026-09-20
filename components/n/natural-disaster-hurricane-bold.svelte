<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le9zsubzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le9zsubzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:natural-disaster-hurricane-bold" {...props}></Icon>
