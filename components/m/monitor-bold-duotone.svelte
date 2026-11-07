<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0ntbnb-n.css';
import '../../css/s/s7ykjoo1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0ntbnb-n"/><path class="s7ykjoo1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:monitor-bold-duotone" {...props}></Icon>
