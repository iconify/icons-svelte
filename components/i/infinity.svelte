<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9an_9pbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9an_9pbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:infinity" {...props}></Icon>
