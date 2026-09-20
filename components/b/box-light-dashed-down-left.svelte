<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1jw05y-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="f1jw05y-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-dashed-down-left" {...props}></Icon>
