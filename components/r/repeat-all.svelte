<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl2zqn34s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="fl2zqn34s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:repeat-all" {...props}></Icon>
