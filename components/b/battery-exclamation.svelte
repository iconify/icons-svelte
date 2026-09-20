<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul432mbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul432mbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-exclamation" {...props}></Icon>
