<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo56a125d.css';
import '../../css/j/je4d_rxfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo56a125d"/><path class="je4d_rxfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:charging-outline" {...props}></Icon>
