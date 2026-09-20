<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j21tacc4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j21tacc4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:digg" {...props}></Icon>
