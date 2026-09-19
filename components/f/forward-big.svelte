<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx8s92bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx8s92bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:forward-big" {...props}></Icon>
