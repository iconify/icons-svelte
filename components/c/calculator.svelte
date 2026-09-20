<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6_i_wbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6_i_wbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:calculator" {...props}></Icon>
