<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwmv9riji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwmv9riji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:filter-off-filled" {...props}></Icon>
