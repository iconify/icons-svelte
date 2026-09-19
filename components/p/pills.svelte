<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1b3226np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1b3226np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:pills" {...props}></Icon>
