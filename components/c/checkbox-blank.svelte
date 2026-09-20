<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5iwp7g-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="z5iwp7g-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:checkbox-blank" {...props}></Icon>
