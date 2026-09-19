<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni1tqcc4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ni1tqcc4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:line-chart-26" {...props}></Icon>
