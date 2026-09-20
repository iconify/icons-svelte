<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ywxbc-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="o3ywxbc-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:calendar-import" {...props}></Icon>
