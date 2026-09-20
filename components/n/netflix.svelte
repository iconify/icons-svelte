<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcjjm57yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcjjm57yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:netflix" {...props}></Icon>
