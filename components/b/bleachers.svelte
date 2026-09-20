<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2vo2fw5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w2vo2fw5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bleachers" {...props}></Icon>
