<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9vnh1heq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9vnh1heq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:map-alt" {...props}></Icon>
