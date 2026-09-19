<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tui4rphfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tui4rphfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-badge" {...props}></Icon>
