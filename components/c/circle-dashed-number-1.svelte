<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frn3o4jqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frn3o4jqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-number-1" {...props}></Icon>
