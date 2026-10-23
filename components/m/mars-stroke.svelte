<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxd8x6rnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxd8x6rnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mars-stroke" {...props}></Icon>
