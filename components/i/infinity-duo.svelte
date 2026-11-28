<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvg6edodd.css';
import '../../css/d/d9an_9pbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvg6edodd secondary"/><path class="d9an_9pbc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:infinity-duo" {...props}></Icon>
