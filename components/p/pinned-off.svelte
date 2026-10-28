<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz7n2ea9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mz7n2ea9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pinned-off" {...props}></Icon>
