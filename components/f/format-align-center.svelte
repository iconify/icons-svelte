<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfd6kjw2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yfd6kjw2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-align-center" {...props}></Icon>
