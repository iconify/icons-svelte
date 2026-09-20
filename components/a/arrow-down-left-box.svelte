<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em5qjuh7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="em5qjuh7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-down-left-box" {...props}></Icon>
