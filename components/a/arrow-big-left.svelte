<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dybqn6b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dybqn6b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-left" {...props}></Icon>
