<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx8nb4mqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx8nb4mqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-left3" {...props}></Icon>
