<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1q_0bcvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1q_0bcvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-minus-line" {...props}></Icon>
