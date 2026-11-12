<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx6xf8bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx6xf8bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-x" {...props}></Icon>
