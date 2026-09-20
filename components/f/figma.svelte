<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f79e7ub9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f79e7ub9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:figma" {...props}></Icon>
