<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp04_1btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp04_1btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-plane" {...props}></Icon>
