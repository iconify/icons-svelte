<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_v4fzbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_v4fzbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folders-plus" {...props}></Icon>
