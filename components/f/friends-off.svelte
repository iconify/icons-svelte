<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6vr9snca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6vr9snca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:friends-off" {...props}></Icon>
