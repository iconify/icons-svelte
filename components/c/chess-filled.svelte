<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni4yygb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni4yygb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chess-filled" {...props}></Icon>
