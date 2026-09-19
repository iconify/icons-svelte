<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4i4jqjrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4i4jqjrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:prusa-mk4" {...props}></Icon>
