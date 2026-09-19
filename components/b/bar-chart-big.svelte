<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdyb6n7ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdyb6n7ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bar-chart-big" {...props}></Icon>
