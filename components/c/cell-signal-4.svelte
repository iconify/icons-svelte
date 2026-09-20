<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnlobh0gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnlobh0gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cell-signal-4" {...props}></Icon>
