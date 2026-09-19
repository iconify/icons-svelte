<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ro7qbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ro7qbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:git-pull-request-closed" {...props}></Icon>
