<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc7o19beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc7o19beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-80-small" {...props}></Icon>
