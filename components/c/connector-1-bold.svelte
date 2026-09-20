<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6-3i_q-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6-3i_q-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:connector-1-bold" {...props}></Icon>
