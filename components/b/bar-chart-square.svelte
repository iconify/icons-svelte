<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8tsarjvu.css';
import '../../css/j/jpoubbo_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8tsarjvu"/><path class="jpoubbo_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bar-chart-square" {...props}></Icon>
