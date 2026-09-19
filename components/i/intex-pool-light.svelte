<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu5dc43kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu5dc43kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:intex-pool-light" {...props}></Icon>
