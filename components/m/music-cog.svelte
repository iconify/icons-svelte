<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk88anb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk88anb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:music-cog" {...props}></Icon>
