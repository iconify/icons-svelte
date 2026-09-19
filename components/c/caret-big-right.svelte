<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8-oypbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8-oypbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-big-right" {...props}></Icon>
