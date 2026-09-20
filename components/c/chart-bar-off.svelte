<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqo1j5b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqo1j5b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-bar-off" {...props}></Icon>
