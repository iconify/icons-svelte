<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljfx7hdpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljfx7hdpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:bus" {...props}></Icon>
