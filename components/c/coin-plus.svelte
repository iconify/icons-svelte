<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kupaqeb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kupaqeb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:coin-plus" {...props}></Icon>
