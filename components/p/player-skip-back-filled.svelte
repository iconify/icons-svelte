<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_i0ahlhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_i0ahlhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-skip-back-filled" {...props}></Icon>
