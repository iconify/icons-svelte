<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tco8aibtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tco8aibtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dice-2-filled" {...props}></Icon>
