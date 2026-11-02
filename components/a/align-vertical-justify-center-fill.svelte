<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd0nw9kca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd0nw9kca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-justify-center-fill" {...props}></Icon>
