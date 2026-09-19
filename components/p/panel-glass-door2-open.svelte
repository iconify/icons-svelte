<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy3q7pbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy3q7pbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-glass-door2-open" {...props}></Icon>
