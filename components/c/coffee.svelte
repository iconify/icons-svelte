<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll3175uwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll3175uwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:coffee" {...props}></Icon>
