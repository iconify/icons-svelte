<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bigxvtqzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bigxvtqzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:monitor-image" {...props}></Icon>
