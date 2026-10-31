<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd8dqt85z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd8dqt85z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-duocolor-round" {...props}></Icon>
