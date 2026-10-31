<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqn6o2rec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqn6o2rec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-1-fill-round" {...props}></Icon>
