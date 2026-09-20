<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdkhoxb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="mdkhoxb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:day-hail" {...props}></Icon>
