<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-b6p1bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-b6p1bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:monitor-question" {...props}></Icon>
