<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvp7ukhew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvp7ukhew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-quarter" {...props}></Icon>
