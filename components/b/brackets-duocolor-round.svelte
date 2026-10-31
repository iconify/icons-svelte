<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt5htob7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt5htob7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brackets-duocolor-round" {...props}></Icon>
